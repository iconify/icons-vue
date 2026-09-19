<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/o/ou29h-bjq.css';
import '../../css/h/hsmgu8r4l.css';
import '../../css/c/cyfkkj1ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="ou29h-bjq"/><ellipse class="hsmgu8r4l"/><path class="cyfkkj1ox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pumpkin" /></template>
