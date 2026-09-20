<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp9mcwqrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vp9mcwqrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:music-note-2-flat" /></template>
