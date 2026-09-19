<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjdztsbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sjdztsbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:yellow-square" /></template>
