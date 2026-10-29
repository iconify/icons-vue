<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rnl2s3bta.css';
import '../../css/l/limikcbir.css';
import '../../css/y/yo47m6hva.css';
import '../../css/o/osc4domqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rnl2s3bta"/><path class="limikcbir wm-k"/><path class="wm-k yo47m6hva"/><path class="osc4domqp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shopping-cart-sketch" /></template>
