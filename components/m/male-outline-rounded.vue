<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg98r6bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:male-outline-rounded" /></template>
<style>
.xg98r6bag {
  fill: currentColor;
  d: path("M19.5 5.308V9q0 .213-.144.356t-.357.144t-.356-.144T18.5 9V6.233l-5.129 5.084q.495.72.812 1.52T14.5 14.5q0 2.091-1.454 3.546T9.502 19.5t-3.546-1.454T4.5 14.502t1.455-3.546T9.5 9.5q.864 0 1.654.315q.79.314 1.504.814L17.787 5.5H15q-.213 0-.356-.144t-.144-.357t.144-.356T15 4.5h3.692q.344 0 .576.232t.232.576M6.67 11.672Q5.5 12.845 5.5 14.503q0 1.659 1.172 2.828Q7.845 18.5 9.503 18.5q1.659 0 2.828-1.172q1.169-1.173 1.169-2.831t-1.172-2.828T9.497 10.5t-2.828 1.172");
}

</style>
