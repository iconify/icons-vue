<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-svt8bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-svt8bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:speech-bubble-rtl" /></template>
