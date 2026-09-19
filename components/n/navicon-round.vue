<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_spqu3na.css';
import '../../css/y/y5xx1ubma.css';
import '../../css/m/mjv9actef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_spqu3na"/><path class="y5xx1ubma"/><path class="mjv9actef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:navicon-round" /></template>
