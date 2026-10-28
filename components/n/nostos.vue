<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7b6qsb4o.css';
import '../../css/j/ju78x-kpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m7b6qsb4o"/><path class="ju78x-kpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nostos" /></template>
