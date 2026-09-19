<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b7xpmx4yq.css';
import '../../css/d/djxnh6jds.css';
import '../../css/m/m-hyl7b5z.css';
import '../../css/c/cq_t3epub.css';
import '../../css/j/jl7gm-a6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b7xpmx4yq"/><path class="djxnh6jds"/><path class="m-hyl7b5z"/><path class="cq_t3epub"/><rect class="jl7gm-a6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:shapes" /></template>
