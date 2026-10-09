<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7xnc1b0i.css';
import '../../css/u/ucg2xpeqq.css';
import '../../css/l/l7hzbkbbx.css';
import '../../css/m/mw2wz86ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m7xnc1b0i"/><path class="ucg2xpeqq"/><path class="l7hzbkbbx"/><path class="mw2wz86ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:supermarket-20-bold" /></template>
