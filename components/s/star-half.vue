<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8dzrhbsa.css';
import '../../css/i/i91j8nbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8dzrhbsa"/><path class="i91j8nbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:star-half" /></template>
