<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iktrg_pfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iktrg_pfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:video-off-filled" /></template>
