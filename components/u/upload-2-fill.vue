<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wii5yeryb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wii5yeryb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:upload-2-fill" /></template>
