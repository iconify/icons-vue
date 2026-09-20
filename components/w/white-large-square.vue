<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb-pr3vku.css';
import '../../css/u/u8r4mnbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="rb-pr3vku"/><path class="u8r4mnbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-large-square" /></template>
