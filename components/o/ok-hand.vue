<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luy7zjvha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="luy7zjvha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ok-hand" /></template>
