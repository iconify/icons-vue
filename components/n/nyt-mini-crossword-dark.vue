<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj67j_bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zj67j_bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-mini-crossword-dark" /></template>
