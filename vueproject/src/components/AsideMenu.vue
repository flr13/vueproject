<template>
  <div>
    <el-radio-group v-model="isCollapse" style="margin-bottom: 20px">
      <el-radio-button :label="false">展开</el-radio-button>
      <el-radio-button :label="true">收起</el-radio-button>
    </el-radio-group>
    <el-menu
      default-active="1-4-1"
      class="el-menu-vertical-demo"
      @open="handleOpen"
      @close="handleClose"
      :collapse="isCollapse"
    >
    
    </el-menu>
  </div>
</template>

<script>
export default {
  name: "AsideMenu",
  components: {},
  props: {},
  data() {
    return {

    }
  },
  created() {},
  mounted() {},
  methods: {}
};
</script>

<style scoped lang="less">
</style>
