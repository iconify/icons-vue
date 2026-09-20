<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0pn9dbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0pn9dbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:map-solid" /></template>
