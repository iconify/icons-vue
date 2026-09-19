<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd4fdd5ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sd4fdd5ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:reminder-ribbon" /></template>
