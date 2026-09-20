<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg8d1vmug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg8d1vmug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:parentheses-line" /></template>
