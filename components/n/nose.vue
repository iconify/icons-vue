<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u35ud5unf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u35ud5unf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:nose" /></template>
