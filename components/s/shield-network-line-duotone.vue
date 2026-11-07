<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/noff7ob6h.css';
import '../../css/r/r5fahkzon.css';
import '../../css/k/koiq71blg.css';
import '../../css/t/tokx6ighc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="noff7ob6h"/><path class="r5fahkzon"/><path class="koiq71blg"/><path class="tokx6ighc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-network-line-duotone" /></template>
