<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vd5gwrbhz.css';
import '../../css/l/l3iub1bhv.css';
import '../../css/o/o5esmw4te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="cuyn6tgcc"><path class="vd5gwrbhz"/><path class="l3iub1bhv"/><path class="o5esmw4te"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-octocat" /></template>
