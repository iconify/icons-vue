<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyg45n2yc.css';
import '../../css/h/htonzo4-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xyg45n2yc"/><path class="htonzo4-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopile-48-bold" /></template>
