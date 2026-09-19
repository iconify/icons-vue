<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3ytobbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b3ytobbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-alpha-down" /></template>
