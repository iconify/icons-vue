<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/ks04zcb2b.css';
import '../../css/o/o-tvj_5su.css';
import '../../css/y/y0cxd-7om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ks04zcb2b"/><path class="o-tvj_5su"/><path class="y0cxd-7om"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-linear" /></template>
