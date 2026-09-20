<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lywattbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lywattbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:supermarket-14" /></template>
