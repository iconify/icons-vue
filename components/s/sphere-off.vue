<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo4g38uvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo4g38uvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sphere-off" /></template>
