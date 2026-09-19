<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knc_ocbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knc_ocbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:new-moon-face" /></template>
