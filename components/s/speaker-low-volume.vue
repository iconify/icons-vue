<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu_m8k-dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eu_m8k-dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:speaker-low-volume" /></template>
