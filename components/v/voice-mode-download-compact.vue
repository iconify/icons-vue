<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvtmg0bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cvtmg0bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:voice-mode-download-compact" /></template>
