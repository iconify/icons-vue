<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm295izdf.css';
import '../../css/f/faw5_bbxe.css';
import '../../css/l/lkg0w6bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm295izdf"/><path class="faw5_bbxe"/><path class="lkg0w6bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:time-of-use-48" /></template>
