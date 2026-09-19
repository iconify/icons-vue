<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-sd1yvj.css';
import '../../css/p/pix652y1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iy-sd1yvj"/><path class="pix652y1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:shield-half-outline" /></template>
