<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpw3o1bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpw3o1bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-off-round" /></template>
