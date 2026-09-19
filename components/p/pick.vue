<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osfx-_bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="osfx-_bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pick" /></template>
