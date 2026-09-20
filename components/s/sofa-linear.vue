<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ncb20ka2n.css';
import '../../css/l/l4pr92b0j.css';
import '../../css/t/tep48fbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ncb20ka2n"/><path class="l4pr92b0j"/><path class="tep48fbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-linear" /></template>
