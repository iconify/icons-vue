<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q0xyh2jup.css';
import '../../css/b/brky1z3rd.css';
import '../../css/i/il2e5rb3k.css';
import '../../css/y/yuw3kybxu.css';
import '../../css/c/cb4xa7b7q.css';
import '../../css/a/apcfd0bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><ellipse class="q0xyh2jup"/><path clip-rule="evenodd" class="brky1z3rd"/><path clip-rule="evenodd" class="il2e5rb3k"/><path clip-rule="evenodd" class="yuw3kybxu"/><path clip-rule="evenodd" class="cb4xa7b7q"/><path clip-rule="evenodd" class="apcfd0bmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:tornado" /></template>
