<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocr_1acml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocr_1acml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swan-breeze" /></template>
