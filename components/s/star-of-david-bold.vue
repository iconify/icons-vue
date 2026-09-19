<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5ku_nt-d.css';
import '../../css/q/q4k0wbbrb.css';
import '../../css/y/yi5t2jbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="j5ku_nt-d"><path class="q4k0wbbrb"/><path class="yi5t2jbyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-of-david-bold" /></template>
