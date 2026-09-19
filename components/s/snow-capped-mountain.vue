<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkuu9-b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tkuu9-b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:snow-capped-mountain" /></template>
