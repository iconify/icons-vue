<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/ttt_csb7t.css';
import '../../css/o/of7zr8bta.css';
import '../../css/c/cnjv6tbhg.css';
import '../../css/a/ahhmpg2xe.css';
import '../../css/z/zc0n0bboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ttt_csb7t"/><path class="of7zr8bta"/><path clip-rule="evenodd" class="cnjv6tbhg"/><path class="ahhmpg2xe"/><path clip-rule="evenodd" class="zc0n0bboj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:monitor2" /></template>
