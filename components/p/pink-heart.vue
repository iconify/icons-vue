<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_trbkfzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="w_trbkfzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pink-heart" /></template>
