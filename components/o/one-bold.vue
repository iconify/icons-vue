<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwa99fblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uwa99fblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:one-bold" /></template>
