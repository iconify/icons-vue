<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ay2e4vb3i"/><path class="nth3xdbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:text-repeater" /></template>
<style>
.ay2e4vb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.922 18.367v-5.983a2.265 2.265 0 0 0-2.265-2.265H6.765A2.265 2.265 0 0 0 4.5 12.384V27.46a2.265 2.265 0 0 0 2.265 2.265h1.24v5.578l6.23-5.578h6.48");
}

.nth3xdbuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.464 18.364h19.283c.968 0 1.753.785 1.753 1.753v11.687c0 .968-.785 1.753-1.753 1.753h-.958v4.324l-4.827-4.324H22.464a1.753 1.753 0 0 1-1.753-1.753V20.117c0-.968.784-1.753 1.753-1.753");
}

</style>
