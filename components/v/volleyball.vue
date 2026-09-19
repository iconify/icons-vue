<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffys-06sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="ffys-06sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:volleyball" /></template>
