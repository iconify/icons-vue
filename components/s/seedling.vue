<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sid-gjbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sid-gjbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seedling" /></template>
