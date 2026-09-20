<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhmi6-ziu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhmi6-ziu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-on-ai-fill" /></template>
