<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs_mrfbth.css';
import '../../css/d/d8wtm6fzz.css';
import '../../css/s/s-_36ob_z.css';
import '../../css/h/hn4yhgb1r.css';
import '../../css/f/fj-t_5o_k.css';
import '../../css/t/t53dib6cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<defs><path id="SVG3YeGgjvy" class="hs_mrfbth"/><path id="SVGeNodGd5V" class="d8wtm6fzz"/></defs><use href="#SVG3YeGgjvy"/><use href="#SVG3YeGgjvy"/><path class="s-_36ob_z"/><use href="#SVGeNodGd5V"/><use href="#SVGeNodGd5V"/><path class="hn4yhgb1r"/><path class="fj-t_5o_k"/><path class="t53dib6cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:ticket" /></template>
