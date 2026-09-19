<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzgf6_ocr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzgf6_ocr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:overmind" /></template>
