<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uygytjt8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uygytjt8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:t" /></template>
