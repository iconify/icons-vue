<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9j0h5ort.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9j0h5ort"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:voice-scan" /></template>
