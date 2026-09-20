<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vw_7vf50q.css';
import '../../css/z/zjjwdmb_w.css';
import '../../css/h/h1a9_kbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vw_7vf50q"/><path class="zjjwdmb_w"/><path class="h1a9_kbwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:recive-twice-square-linear" /></template>
