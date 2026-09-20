<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/ozix77-sy.css';
import '../../css/s/sl9uo94_w.css';
import '../../css/f/f4kpv4bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ozix77-sy"/><path class="sl9uo94_w"/><path class="f4kpv4bkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-open-dashed-sharp-duotone" /></template>
