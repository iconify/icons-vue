<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/np63e2b1o.css';
import '../../css/p/p0q2sxjnz.css';
import '../../css/h/hqyg-9bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="np63e2b1o"/><path class="p0q2sxjnz wm-a"/><path class="hqyg-9bir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:traffic-light-duo" /></template>
