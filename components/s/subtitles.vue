<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz3vw27bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz3vw27bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:subtitles" /></template>
