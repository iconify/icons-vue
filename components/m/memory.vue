<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkb26011h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkb26011h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:memory" /></template>
