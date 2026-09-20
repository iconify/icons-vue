<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0maw-bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":841.89,"height":595.28};
const content = `<path class="e0maw-bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xai-grok-dark" /></template>
