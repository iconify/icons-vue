<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zdhvhb4hv.css';
import '../../css/r/rhpb7tbqf.css';
import '../../css/u/u_fqmub8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zdhvhb4hv"/><path class="rhpb7tbqf"/><path class="u_fqmub8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:secured-network" /></template>
