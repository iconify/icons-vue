<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1oyvcbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:molecule" /></template>
<style>
.b1oyvcbuo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.25Q8.25 4.25 8.25 8q0 1.642.719 2.565l-1.652 1.983q-.759-.298-1.817-.298q-3.75 0-3.75 3.75t3.75 3.75T9.25 16q0-1.642-.719-2.565l1.652-1.983q.759.298 1.817.298t1.817-.298l1.652 1.983q-.719.923-.719 2.565q0 3.75 3.75 3.75T22.25 16t-3.75-3.75q-1.058 0-1.817.298l-1.652-1.983q.719-.923.719-2.565q0-3.75-3.75-3.75");
}

</style>
