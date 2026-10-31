<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v11c6jlnw.css';
import '../../css/d/dh0935bbc.css';
import '../../css/s/soey5ibpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v11c6jlnw wm-k"/><path class="dh0935bbc wm-shine"/><path class="soey5ibpc wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:newspaper" /></template>
