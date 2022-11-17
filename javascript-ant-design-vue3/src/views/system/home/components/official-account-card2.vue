<!--
  * 联系我们
  * 
  * @Author:    OMG
  * @Date:      2022-11-16 10:45:43
  * @Wechat:    OMG_ZSW
  * @Copyright  深圳欧米高
  *
-->
<template>
  <default-home-card icon="SmileTwoTone" title="联系我们">
     <div class="lxI">
       <el-row :gutter="20">
         <el-col :span="11"><div class="testCol"><span>小王：</span>&nbsp;&nbsp;&nbsp;&nbsp;13748914038</div></el-col>
         <el-col :span="11"><div class="testCol">张雷一：13575896248</div></el-col>
       </el-row>
       <el-row :gutter="20">
         <el-col :span="11"><div class="testCol">张王工：15685486358</div></el-col>
         <el-col :span="11"><div class="testCol"><span>小王：</span>&nbsp;&nbsp;&nbsp;&nbsp;16945223846</div></el-col>
       </el-row>
     </div>
  </default-home-card>
</template>
<script setup>
  import DefaultHomeCard from '/@/views/system/home/components/default-home-card.vue';
</script>
<style lang="less" scoped>
   .lxI {
     height:60px;
     .testCol {
       font-size: 16px;
       overflow-x: hidden;
     }
   }
</style>
