<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9o733qam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1664};
const content = `<path class="z9o733qam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:power-off" /></template>
