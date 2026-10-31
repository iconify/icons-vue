<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhjf6rbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhjf6rbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stethoscope-fill-round" /></template>
