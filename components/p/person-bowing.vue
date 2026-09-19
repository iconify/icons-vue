<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl89ysb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wl89ysb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-bowing" /></template>
