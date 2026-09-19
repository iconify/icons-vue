<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3k9iwbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e3k9iwbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:roller-coaster" /></template>
