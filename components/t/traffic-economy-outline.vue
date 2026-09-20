<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/frvs39b5t.css';
import '../../css/k/k5ikzyb2n.css';
import '../../css/b/bv162rb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="frvs39b5t"/><path class="k5ikzyb2n"/><path class="bv162rb1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:traffic-economy-outline" /></template>
