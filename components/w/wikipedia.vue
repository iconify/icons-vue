<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpmh16bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="wpmh16bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wikipedia" /></template>
