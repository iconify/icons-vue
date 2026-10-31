<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwhof2_ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwhof2_ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-round" /></template>
