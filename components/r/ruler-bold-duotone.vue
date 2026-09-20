<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m7vbzuguv.css';
import '../../css/p/p6hck1blo.css';
import '../../css/b/bx67anwvz.css';
import '../../css/b/bvisy3whf.css';
import '../../css/w/w83w87a_a.css';
import '../../css/g/g8x168b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m7vbzuguv"/><path class="p6hck1blo"/><path class="bx67anwvz"/><path class="bvisy3whf"/><path class="w83w87a_a"/><path class="g8x168b0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-bold-duotone" /></template>
