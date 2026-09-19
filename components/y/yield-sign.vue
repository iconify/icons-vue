<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1757qb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="u1757qb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:yield-sign" /></template>
