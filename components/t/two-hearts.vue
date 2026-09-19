<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh1r_abuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eh1r_abuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:two-hearts" /></template>
