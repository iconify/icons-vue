<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fltzu3bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fltzu3bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-plus-outline" /></template>
