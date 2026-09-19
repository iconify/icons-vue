<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro5bd-b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ro5bd-b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:revolving-hearts" /></template>
