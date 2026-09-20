<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ejo52khxn.css';
import '../../css/h/hmwu_nbej.css';
import '../../css/h/hlmlrw03c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ejo52khxn"/><path class="hmwu_nbej"/><path class="hlmlrw03c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler-pen-duotone" /></template>
