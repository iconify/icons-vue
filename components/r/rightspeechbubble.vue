<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-0yqlbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-0yqlbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:rightspeechbubble" /></template>
