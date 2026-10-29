<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/ch4j9abio.css';
import '../../css/p/pm96j7xxh.css';
import '../../css/w/wiker-buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ch4j9abio"/><path class="pm96j7xxh wm-a"/><path class="wiker-buu wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smartphone-message" /></template>
