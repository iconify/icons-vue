<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbgiu0boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gbgiu0boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:top-arrow" /></template>
