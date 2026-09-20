<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh5ep_9os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh5ep_9os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:memory-stick" /></template>
