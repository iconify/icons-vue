<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcgo1w6kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lcgo1w6kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-strands-dark" /></template>
