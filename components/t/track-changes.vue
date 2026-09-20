<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnai3j2qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnai3j2qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:track-changes" /></template>
