<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j32mcj-1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-info-sharp" /></template>
<style>
.j32mcj-1g {
  fill: currentColor;
  d: path("M15.088 19.163Q14 18.075 14 16.5t1.088-2.662t2.662-1.088t2.663 1.088T21.5 16.5t-1.088 2.663t-2.662 1.087t-2.662-1.088M4 17.5v-2h8v2zm-.413-7.337Q2.5 9.075 2.5 7.5t1.088-2.662T6.25 3.75t2.663 1.088T10 7.5t-1.088 2.663T6.25 11.25t-2.662-1.088M12 8.5v-2h8v2z");
}

</style>
