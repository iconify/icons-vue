<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/die20-bcf.css';
import '../../css/q/qqww5s1hy.css';
import '../../css/p/pd8vt0rck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><circle class="die20-bcf"/><path class="qqww5s1hy"/><path class="pd8vt0rck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:route-arrow" /></template>
