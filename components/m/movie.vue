<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwo5t8b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwo5t8b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:movie" /></template>
