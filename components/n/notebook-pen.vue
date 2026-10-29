<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u8djjoheg.css';
import '../../css/m/mqfx5dq5o.css';
import '../../css/w/w9pcj6b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="u8djjoheg"/><path class="mqfx5dq5o wm-a"/><path class="w9pcj6b5h wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:notebook-pen" /></template>
