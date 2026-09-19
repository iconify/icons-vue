<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s06ydqbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="s06ydqbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:panorama-horizontal" /></template>
