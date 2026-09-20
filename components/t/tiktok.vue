<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4ofsv3me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ofsv3me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:tiktok" /></template>
