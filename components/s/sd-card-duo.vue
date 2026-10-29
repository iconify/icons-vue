<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qyyoq8bgz.css';
import '../../css/g/go3ojebxo.css';
import '../../css/a/abasntp2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qyyoq8bgz"/><path class="go3ojebxo wm-a"/><path class="abasntp2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sd-card-duo" /></template>
