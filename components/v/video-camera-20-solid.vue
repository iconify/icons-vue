<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwy8aw0id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rwy8aw0id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:video-camera-20-solid" /></template>
