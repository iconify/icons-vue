<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yowlgqbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yowlgqbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-climbing" /></template>
