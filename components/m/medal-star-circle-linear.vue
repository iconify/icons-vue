<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lebqn5bme.css';
import '../../css/l/l_3c_lb_q.css';
import '../../css/q/qxdu-bceo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lebqn5bme"/><circle class="l_3c_lb_q"/><path class="qxdu-bceo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-circle-linear" /></template>
