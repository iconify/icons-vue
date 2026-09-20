<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oxq7w1buj"/><path class="tvwpl1bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:npm-icon" /></template>
<style>
.oxq7w1buj {
  fill: var(--svg-color--c12127, #c12127);
  d: path("M0 256V0h256v256z");
}

.tvwpl1bgp {
  fill: var(--svg-color--fff, #fff);
  d: path("M48 48h160v160h-32V80h-48v128H48z");
}

</style>
