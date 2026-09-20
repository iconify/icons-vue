<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c525xyy-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c525xyy-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-slider-2-bold" /></template>
