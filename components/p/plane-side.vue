<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyf_n7bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zyf_n7bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plane-side" /></template>
