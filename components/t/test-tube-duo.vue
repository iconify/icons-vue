<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lsy6r8esb.css';
import '../../css/f/fjsedw-yo.css';
import '../../css/c/cfmykrbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lsy6r8esb"/><path class="fjsedw-yo wm-a"/><path class="cfmykrbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:test-tube-duo" /></template>
