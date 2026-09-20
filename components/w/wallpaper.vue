<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sma7-s9ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sma7-s9ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wallpaper" /></template>
