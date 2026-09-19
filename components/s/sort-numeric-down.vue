<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr2383hrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vr2383hrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-numeric-down" /></template>
