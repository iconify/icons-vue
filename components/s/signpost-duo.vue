<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u1jdk2vpr.css';
import '../../css/e/e--mbmb3x.css';
import '../../css/d/d59m1yvcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="u1jdk2vpr"/><path class="e--mbmb3x wm-a"/><path class="d59m1yvcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:signpost-duo" /></template>
