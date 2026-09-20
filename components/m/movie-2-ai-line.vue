<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm95ujemq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm95ujemq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:movie-2-ai-line" /></template>
