<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmy4bkbyv.css';
import '../../css/m/mh8yf9b3b.css';
import '../../css/e/ed4mxccbx.css';
import '../../css/e/eqdr87b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tmy4bkbyv"/><path class="mh8yf9b3b"/><path class="ed4mxccbx"/><path class="eqdr87b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:router-x-20" /></template>
