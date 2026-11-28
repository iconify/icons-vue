<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na6slrbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na6slrbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:security-camera-check" /></template>
