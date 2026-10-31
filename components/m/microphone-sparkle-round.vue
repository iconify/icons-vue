<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snlsb6x6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snlsb6x6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-sparkle-round" /></template>
