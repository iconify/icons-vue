<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh8gqdp9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh8gqdp9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:phone-camera-line" /></template>
