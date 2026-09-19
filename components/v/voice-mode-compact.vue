<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvbu6bbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qvbu6bbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:voice-mode-compact" /></template>
