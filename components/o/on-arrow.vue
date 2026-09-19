<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vla2mvb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vla2mvb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:on-arrow" /></template>
