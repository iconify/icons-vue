<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0alxpbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v0alxpbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:zoom-out" /></template>
