<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuu6rzmsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vuu6rzmsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:part-alternation-mark" /></template>
