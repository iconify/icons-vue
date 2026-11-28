<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpi8b_n1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpi8b_n1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:security-camera-check" /></template>
