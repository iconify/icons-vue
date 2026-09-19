<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhnlb3m2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vhnlb3m2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:modulo" /></template>
