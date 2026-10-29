<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xjy703kxm.css';
import '../../css/h/hbi8hhkfx.css';
import '../../css/b/bp8ecnj5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xjy703kxm"/><path class="hbi8hhkfx wm-a"/><path class="bp8ecnj5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:settings-duo" /></template>
