<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtflctbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vtflctbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:video-camera-slash-16-solid" /></template>
