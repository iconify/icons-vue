<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a23d2obbm.css';
import '../../css/g/gj72yxbju.css';
import '../../css/x/xpke-abpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="a23d2obbm"/><path clip-rule="evenodd" class="gj72yxbju"/><path class="xpke-abpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:timer-fast-bold" /></template>
