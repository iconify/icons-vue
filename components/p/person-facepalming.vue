<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i91je5b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i91je5b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-facepalming" /></template>
