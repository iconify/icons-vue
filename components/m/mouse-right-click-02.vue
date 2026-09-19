<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qj1iru8vv.css';
import '../../css/t/tn42p5bue.css';
import '../../css/r/rzggd57gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qj1iru8vv"/><path class="tn42p5bue"/><circle transform="matrix(-1 0 0 1 20 2.5)" class="rzggd57gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-right-click-02" /></template>
