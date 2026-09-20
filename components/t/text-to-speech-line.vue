<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i174zxb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i174zxb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:text-to-speech-line" /></template>
