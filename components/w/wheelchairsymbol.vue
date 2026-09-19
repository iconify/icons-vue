<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4xf1bb5l.css';
import '../../css/r/r8hexeb-r.css';
import '../../css/c/cdedgs6la.css';
import '../../css/a/a0p8v79-c.css';
import '../../css/p/pox_jy--p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4xf1bb5l"/><path class="r8hexeb-r"/><circle class="cdedgs6la"/><path class="a0p8v79-c"/><path class="pox_jy--p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:wheelchairsymbol" /></template>
