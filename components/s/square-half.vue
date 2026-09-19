<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4wkd6b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z4wkd6b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:square-half" /></template>
