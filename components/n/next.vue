<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptdi0xbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptdi0xbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:next" /></template>
