<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr_2ikhqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gr_2ikhqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:zero" /></template>
