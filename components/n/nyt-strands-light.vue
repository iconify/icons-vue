<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7rxhcc7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7rxhcc7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-strands-light" /></template>
