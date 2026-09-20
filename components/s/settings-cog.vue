<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3bwx9b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3bwx9b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:settings-cog" /></template>
