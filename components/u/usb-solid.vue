<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvqi0ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqi0ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:usb-solid" /></template>
