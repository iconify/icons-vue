<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qal-z721q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qal-z721q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-1" /></template>
