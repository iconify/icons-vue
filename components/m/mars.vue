<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/w/w0v5p4b8e.css';
import '../../css/v/vd7gt8b1z.css';
import '../../css/u/unie4db7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="w0v5p4b8e"/><path class="vd7gt8b1z"/><path class="unie4db7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:mars" /></template>
