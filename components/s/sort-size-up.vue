<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaw_gqb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="aaw_gqb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-size-up" /></template>
