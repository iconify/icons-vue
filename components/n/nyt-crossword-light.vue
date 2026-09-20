<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hixc0gbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hixc0gbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-crossword-light" /></template>
