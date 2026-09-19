<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-06_rfwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-06_rfwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:palm-up-hand" /></template>
