<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ald82rf_n.css';
import '../../css/k/k8-wr-pvm.css';
import '../../css/n/nz0ig3adr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ald82rf_n"/><path class="k8-wr-pvm"/><path class="nz0ig3adr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:prisoner" /></template>
