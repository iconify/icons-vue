<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crk11mb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-real-size-outline-rounded" /></template>
<style>
.crk11mb_c {
  fill: currentColor;
  d: path("M7.97 15.856q-.143-.143-.143-.356V9.327q0-.135-.096-.23Q7.635 9 7.5 9h-1q-.213 0-.356-.144T6 8.499t.144-.356T6.5 8h1.116q.504 0 .858.353q.353.354.353.858V15.5q0 .213-.144.356T8.326 16t-.356-.144m8.173 0Q16 15.713 16 15.5V9.327q0-.135-.096-.23Q15.808 9 15.673 9h-.98q-.213 0-.357-.144t-.144-.357t.144-.356t.356-.143h1.096q.505 0 .859.353q.353.354.353.858V15.5q0 .213-.144.356t-.357.144t-.356-.144m-4.538-3.5q-.143-.144-.143-.357t.144-.356t.356-.143t.356.144t.144.357t-.144.356t-.357.143t-.356-.144m0 3.5q-.143-.144-.143-.357t.144-.356t.356-.143t.356.144t.144.357t-.144.356t-.357.143t-.356-.144");
}

</style>
