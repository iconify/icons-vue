<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rqp_fpfgv.css';
import '../../css/h/hku-2nb6r.css';
import '../../css/n/ne9k0gz5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rqp_fpfgv"/><path clip-rule="evenodd" class="hku-2nb6r"/><path class="ne9k0gz5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:share-android-print" /></template>
