<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mczdvq7nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mczdvq7nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:video-off" /></template>
