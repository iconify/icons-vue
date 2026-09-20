<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6wx27b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y6wx27b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:media" /></template>
