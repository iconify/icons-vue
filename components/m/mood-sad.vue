<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unt32jbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unt32jbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mood-sad" /></template>
