<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8qllcbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8qllcbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:monitor-sharp" /></template>
