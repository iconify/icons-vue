<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxkzprb8a.css';
import '../../css/l/lscshqmdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gxkzprb8a"/><path class="lscshqmdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-snow-20" /></template>
