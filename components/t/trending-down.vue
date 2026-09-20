<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im1uwjbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im1uwjbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:trending-down" /></template>
