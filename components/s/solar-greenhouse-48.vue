<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgzdi_vdo.css';
import '../../css/l/ll2igp43q.css';
import '../../css/k/kbt7z1_ku.css';
import '../../css/b/bxvsbvbrm.css';
import '../../css/f/f2pwcorxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qgzdi_vdo"/><path class="ll2igp43q"/><path class="kbt7z1_ku"/><path class="bxvsbvbrm"/><path class="f2pwcorxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-greenhouse-48" /></template>
