<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ay8tbubjq.css';
import '../../css/s/sfu0pxbzr.css';
import '../../css/n/n5o__tdls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ay8tbubjq"/><path class="sfu0pxbzr"/><path class="n5o__tdls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wifi-filled" /></template>
