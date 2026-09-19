<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/walnt8bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="walnt8bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:rugby-football" /></template>
