<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5n-ahbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5n-ahbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:window-frame-sharp" /></template>
