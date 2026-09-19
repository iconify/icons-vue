<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz_vbibin.css';
import '../../css/x/xb-o3nqnz.css';
import '../../css/u/u_ozfpbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="qz_vbibin"/><path class="xb-o3nqnz"/><path class="u_ozfpbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:wallet-outline" /></template>
