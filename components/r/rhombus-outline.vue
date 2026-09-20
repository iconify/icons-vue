<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s24s4wb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s24s4wb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rhombus-outline" /></template>
