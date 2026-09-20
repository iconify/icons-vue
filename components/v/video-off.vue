<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dodmv35as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dodmv35as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:video-off" /></template>
