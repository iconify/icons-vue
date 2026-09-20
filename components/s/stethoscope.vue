<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn6572ben.css';
import '../../css/o/ooqed9bmq.css';
import '../../css/m/mdlfzfvqf.css';
import '../../css/v/vrwg7cc1q.css';
import '../../css/l/l_hkwiw8o.css';
import '../../css/g/gv69wtove.css';
import '../../css/h/h04quwjxl.css';
import '../../css/n/nbvb4rbjl.css';
import '../../css/b/bm17p3b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="xn6572ben"/><circle class="ooqed9bmq"/><path class="mdlfzfvqf"/><g class="vrwg7cc1q"><path class="l_hkwiw8o"/><path class="gv69wtove"/><path class="h04quwjxl"/><circle class="nbvb4rbjl"/><path class="bm17p3b7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:stethoscope" /></template>
