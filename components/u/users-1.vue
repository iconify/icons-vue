<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r92jf7bnj.css';
import '../../css/l/lq-c69bty.css';
import '../../css/p/p_af5cb9o.css';
import '../../css/g/g378efbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r92jf7bnj"/><path class="lq-c69bty"/><path class="p_af5cb9o"/><path class="g378efbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:users-1" /></template>
