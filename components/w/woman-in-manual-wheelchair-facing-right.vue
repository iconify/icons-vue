<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_v1zhbtb.css';
import '../../css/d/d5acjcb7w.css';
import '../../css/u/u2kjx6byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_v1zhbtb"/><path class="d5acjcb7w"/><path class="u2kjx6byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-in-manual-wheelchair-facing-right" /></template>
