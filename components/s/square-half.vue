<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cci7y7bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cci7y7bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-half" /></template>
