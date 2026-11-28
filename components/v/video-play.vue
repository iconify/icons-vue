<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhq63ab0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhq63ab0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-play" /></template>
