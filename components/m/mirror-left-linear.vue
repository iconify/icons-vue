<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uspitw7xi.css';
import '../../css/h/h6dnwg9iw.css';
import '../../css/d/dxon-mtqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uspitw7xi"/><path class="h6dnwg9iw"/><path class="dxon-mtqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-left-linear" /></template>
