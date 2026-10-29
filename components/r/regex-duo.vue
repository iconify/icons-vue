<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m1ox2hhhb.css';
import '../../css/l/l-if2ibsb.css';
import '../../css/a/a74ox2l4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m1ox2hhhb"/><path class="l-if2ibsb wm-a"/><path class="a74ox2l4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:regex-duo" /></template>
