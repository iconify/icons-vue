<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj98afbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vj98afbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:threat-browser-1-solid" /></template>
