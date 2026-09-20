<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq_brwbot.css';
import '../../css/p/pcb-afbny.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/d/dlgtz7bzm.css';
import '../../css/b/bf-d5dhwv.css';
import '../../css/w/w4x5njb1k.css';
import '../../css/s/sxaag2b4r.css';
import '../../css/l/ld73wxrvx.css';
import '../../css/r/rlw-a0bwz.css';
import '../../css/m/mjkkyrtpw.css';
import '../../css/h/h1vxc2b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dq_brwbot"/><path class="pcb-afbny"/><g class="jn8qy4bru"><path class="dlgtz7bzm"/><path class="bf-d5dhwv"/><path class="w4x5njb1k"/><path class="sxaag2b4r"/><path class="ld73wxrvx"/><path class="rlw-a0bwz"/><path class="mjkkyrtpw"/><path class="h1vxc2b5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:move" /></template>
