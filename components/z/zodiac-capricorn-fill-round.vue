<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd5mfab7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd5mfab7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-capricorn-fill-round" /></template>
