<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8-7gvb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8-7gvb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-mini-crossword-dark" /></template>
