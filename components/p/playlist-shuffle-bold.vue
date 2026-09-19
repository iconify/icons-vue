<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkqua9d2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkqua9d2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:playlist-shuffle-bold" /></template>
