<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mmq6zvbgf.css';
import '../../css/k/k8mwp_zry.css';
import '../../css/f/fg9hpm71u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mmq6zvbgf"/><path class="k8mwp_zry"/><path class="fg9hpm71u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-minimalistic-broken" /></template>
