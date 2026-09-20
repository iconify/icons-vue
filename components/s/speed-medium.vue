<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr977ni_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr977ni_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:speed-medium" /></template>
