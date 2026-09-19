<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_mejsblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l_mejsblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:quote-single-outline" /></template>
