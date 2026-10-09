<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo64yvbkk.css';
import '../../css/r/r5qp9ebil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xo64yvbkk"/><path class="r5qp9ebil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pencil-48" /></template>
