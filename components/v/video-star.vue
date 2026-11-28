<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on7sy0u4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on7sy0u4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-star" /></template>
