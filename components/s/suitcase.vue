<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mi79qknjq.css';
import '../../css/t/t22r7x1ib.css';
import '../../css/b/bpia10usa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mi79qknjq"/><rect class="t22r7x1ib"/><rect class="bpia10usa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:suitcase" /></template>
