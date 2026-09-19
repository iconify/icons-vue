<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/frd2xy4_s.css';
import '../../css/c/c8uqgwu0z.css';
import '../../css/w/w7szrji6j.css';
import '../../css/u/u3b88k18b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="frd2xy4_s"/><path class="c8uqgwu0z"/><path class="w7szrji6j"/><path class="u3b88k18b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:map-marker-2-outline" /></template>
