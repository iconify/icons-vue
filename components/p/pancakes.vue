<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aivk7ubvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aivk7ubvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pancakes" /></template>
