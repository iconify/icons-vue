<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a30p66bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:sails" /></template>
<style>
.a30p66bsm {
  fill: var(--svg-color--28a3b2, #28a3b2);
  d: path("M24.34 255.334S-73.092 100.291 127.341.457v254.877zm134.033 0V97.36s31.99 52.206 97.003 157.975z");
}

</style>
