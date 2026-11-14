<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m392eubms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:show" /></template>
<style>
.m392eubms {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.75q-7.099 0-10.185 6.945q-.065.146-.065.305t.065.305Q4.901 19.25 12 19.25t10.185-6.945q.065-.146.065-.305t-.065-.305Q19.099 4.75 12 4.75M8.25 12q0-3.75 3.75-3.75T15.75 12T12 15.75T8.25 12");
}

</style>
