<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go64vgysl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="go64vgysl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:medical-symbol" /></template>
