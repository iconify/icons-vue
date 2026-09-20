<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixrh7abjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ixrh7abjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-dot-horizontal-line-in-rectangle" /></template>
