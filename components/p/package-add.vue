<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mu4ajhnbi.css';
import '../../css/s/s6a9woy2h.css';
import '../../css/i/iem8lp2xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mu4ajhnbi"/><path class="s6a9woy2h"/><path class="iem8lp2xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-add" /></template>
