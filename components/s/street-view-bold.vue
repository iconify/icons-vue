<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w8myxrsji.css';
import '../../css/f/fn6lbqmuk.css';
import '../../css/a/afy8xbjmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w8myxrsji"/><path clip-rule="evenodd" class="fn6lbqmuk"/><path class="afy8xbjmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:street-view-bold" /></template>
