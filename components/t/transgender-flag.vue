<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0dbzhzij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v0dbzhzij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:transgender-flag" /></template>
