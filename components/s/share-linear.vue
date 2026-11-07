<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/at_81ebpk.css';
import '../../css/t/tf_8-xb1g.css';
import '../../css/q/qxli02nev.css';
import '../../css/e/ex_z2zb_b.css';
import '../../css/d/d-orjcc8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="at_81ebpk"/><path class="tf_8-xb1g"/><path class="qxli02nev"/><path class="ex_z2zb_b"/><path class="d-orjcc8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-linear" /></template>
