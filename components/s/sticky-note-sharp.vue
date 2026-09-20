<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5zn_wegq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5zn_wegq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sticky-note-sharp" /></template>
