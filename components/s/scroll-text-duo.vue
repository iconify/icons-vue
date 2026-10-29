<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uv7s600ds.css';
import '../../css/u/uc0yabbtt.css';
import '../../css/j/j5ep5hbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uv7s600ds"/><path class="uc0yabbtt wm-a"/><path class="j5ep5hbtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scroll-text-duo" /></template>
