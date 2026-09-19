<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nwgdq5bka.css';
import '../../css/l/l8395c28f.css';
import '../../css/n/nvb3dunuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nwgdq5bka"/><path class="l8395c28f"/><path class="nvb3dunuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tags" /></template>
