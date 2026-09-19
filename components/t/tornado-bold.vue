<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sovy61-7k.css';
import '../../css/j/js5r8hjtc.css';
import '../../css/h/hvqpucqhf.css';
import '../../css/i/i_fevuidw.css';
import '../../css/i/i47ie_bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><ellipse class="sovy61-7k"/><path clip-rule="evenodd" class="js5r8hjtc"/><path clip-rule="evenodd" class="hvqpucqhf"/><path clip-rule="evenodd" class="i_fevuidw"/><path clip-rule="evenodd" class="i47ie_bvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tornado-bold" /></template>
