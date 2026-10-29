<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fs5p-d7vq.css';
import '../../css/c/ciui2qe_b.css';
import '../../css/g/gz4rmvf3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fs5p-d7vq wm-s"/><path class="ciui2qe_b wm-s"/><path class="gz4rmvf3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:text-sparkles-duo" /></template>
