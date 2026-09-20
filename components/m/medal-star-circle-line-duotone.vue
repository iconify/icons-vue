<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dg3lobkil.css';
import '../../css/z/zt4v2yr9g.css';
import '../../css/l/l_3c_lb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dg3lobkil"/><path class="zt4v2yr9g"/><circle class="l_3c_lb_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-circle-line-duotone" /></template>
