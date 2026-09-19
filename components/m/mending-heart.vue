<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6rb31mno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s6rb31mno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mending-heart" /></template>
