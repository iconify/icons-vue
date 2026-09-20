<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0pil_dpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0pil_dpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:terminal-line" /></template>
