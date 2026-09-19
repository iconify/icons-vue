<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-s9sj87a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j-s9sj87a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:squid" /></template>
