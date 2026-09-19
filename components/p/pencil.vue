<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhbi0hb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hhbi0hb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pencil" /></template>
