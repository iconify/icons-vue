<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g23rcvbys.css';
import '../../css/c/cb5q1t0wa.css';
import '../../css/k/ki937_vam.css';
import '../../css/l/legq5bc_c.css';
import '../../css/e/e25_yeuhs.css';
import '../../css/q/qbegytbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g23rcvbys"/><path class="cb5q1t0wa"/><g class="ki937_vam"><path class="legq5bc_c"/><circle class="e25_yeuhs"/><circle class="qbegytbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:serial-tasks" /></template>
