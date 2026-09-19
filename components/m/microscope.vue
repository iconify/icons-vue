<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7eoc6b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x7eoc6b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:microscope" /></template>
