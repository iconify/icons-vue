<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icxlooygs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:navigation" /></template>
<style>
.icxlooygs {
  fill: currentColor;
  d: path("M12 2L4.5 20.29l.71.71L12 18l6.79 3l.71-.71z");
}

</style>
