<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvkzdkbth.css';
import '../../css/j/jiqqgjbyl.css';
import '../../css/q/qdwhrdl3w.css';
import '../../css/z/zwmgmbqzr.css';
import '../../css/r/r7k436bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="mvkzdkbth"/><rect class="jiqqgjbyl"/><path class="qdwhrdl3w"/><path class="zwmgmbqzr"/><circle class="r7k436bkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:wallet-one" /></template>
