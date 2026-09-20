<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv-waabpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv-waabpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-clef-treble" /></template>
