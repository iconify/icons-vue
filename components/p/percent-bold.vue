<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1bmkqy-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="j1bmkqy-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:percent-bold" /></template>
