<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unsnq708q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="unsnq708q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:triangle-left" /></template>
