<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on59fzbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="on59fzbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:skull" /></template>
