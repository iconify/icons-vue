<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anx0eybut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="anx0eybut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:test-tube" /></template>
