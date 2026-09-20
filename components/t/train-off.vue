<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f7jhbfbbm.css';
import '../../css/i/ixdiu-boz.css';
import '../../css/k/kj8-njb7p.css';
import '../../css/t/tapiesbnb.css';
import '../../css/z/zv9ieru2c.css';
import '../../css/l/lbeu2r7gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f7jhbfbbm"/><path clip-rule="evenodd" class="ixdiu-boz"/><path clip-rule="evenodd" class="kj8-njb7p"/><path class="tapiesbnb"/><path clip-rule="evenodd" class="zv9ieru2c"/><path class="lbeu2r7gj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:train-off" /></template>
