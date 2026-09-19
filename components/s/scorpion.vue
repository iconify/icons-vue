<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2fuczbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2fuczbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:scorpion" /></template>
