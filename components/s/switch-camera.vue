<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gub3n7bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gub3n7bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:switch-camera" /></template>
