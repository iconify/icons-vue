<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dykt1tozj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dykt1tozj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:usb" /></template>
