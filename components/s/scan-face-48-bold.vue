<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq2pmabsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qq2pmabsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-face-48-bold" /></template>
