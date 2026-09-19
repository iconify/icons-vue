<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so2clvbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="so2clvbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scissors-open-1-bold" /></template>
