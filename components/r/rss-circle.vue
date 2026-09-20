<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs66k5bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs66k5bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:rss-circle" /></template>
