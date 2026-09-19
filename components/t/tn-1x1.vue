<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srq6p5b9s.css';
import '../../css/g/gxp1ob29q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="srq6p5b9s"/><path class="gxp1ob29q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:tn-1x1" /></template>
