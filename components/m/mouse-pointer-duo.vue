<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rteezzenz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rteezzenz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mouse-pointer-duo" /></template>
