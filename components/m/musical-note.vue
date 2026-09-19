<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu5pueb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nu5pueb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:musical-note" /></template>
