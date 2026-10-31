<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/h/hjo1he0av.css';
import '../../css/q/qd1g9obrp.css';
import '../../css/o/o6s2xc_ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="hjo1he0av wm-shadow"/><path class="qd1g9obrp wm-shadow"/><path class="o6s2xc_ss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:sort-alpha" /></template>
