<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/las96bcjw.css';
import '../../css/v/vz7_ibceo.css';
import '../../css/g/g2ncvrepr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="las96bcjw"/><rect class="vz7_ibceo"/><path class="g2ncvrepr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:server" /></template>
