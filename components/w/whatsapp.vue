<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqeumc3sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="dqeumc3sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:whatsapp" /></template>
