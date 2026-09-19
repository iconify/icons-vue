<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i__int0_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i__int0_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:victory-hand" /></template>
