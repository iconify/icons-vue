<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path clip-rule="evenodd" class="b7060yb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:quad-background" /></template>
<style>
.b7060yb3t {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.4 5.6H5.6v12.8h11.67l-2.667-2.667H8.267V8.267h7.466v6.336l2.667 2.666zM4 4v16h16V4zm5.867 5.867h4.266v4.266H9.867z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

</style>
