<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-o8fpw5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b-o8fpw5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mouse-2-bold" /></template>
