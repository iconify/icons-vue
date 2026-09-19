<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7k1kge9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x7k1kge9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sliders" /></template>
