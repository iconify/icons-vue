<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdzxtab2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-monitor" /></template>
<style>
.zdzxtab2f {
  fill: currentColor;
  d: path("M22 3H2v15h5l-1 1v2h12v-2l-1-1h5zm-2 13H4V5h16z");
}

</style>
