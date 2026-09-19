<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwntz9y7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lwntz9y7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-1-duo" /></template>
