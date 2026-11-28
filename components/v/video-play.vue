<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5c3okjbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5c3okjbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:video-play" /></template>
