<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uw5ylwu1y.css';
import '../../css/z/zk6fj2bpn.css';
import '../../css/p/pltckst1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw5ylwu1y"/><path class="zk6fj2bpn"/><path class="pltckst1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-pin-star" /></template>
