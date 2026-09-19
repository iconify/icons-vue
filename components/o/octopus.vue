<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx4326jil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sx4326jil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:octopus" /></template>
