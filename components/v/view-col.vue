<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdg_7jb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdg_7jb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:view-col" /></template>
