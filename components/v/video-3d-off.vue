<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmtyaabri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmtyaabri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-3d-off" /></template>
