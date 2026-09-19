<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgyo6bb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lgyo6bb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:math-duo" /></template>
