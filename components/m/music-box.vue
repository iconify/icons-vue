<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vszc59cox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vszc59cox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-box" /></template>
