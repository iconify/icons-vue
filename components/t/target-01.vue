<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sn_ghebzo.css';
import '../../css/i/i_l5txb5m.css';
import '../../css/m/mia0evx_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sn_ghebzo"/><path class="i_l5txb5m"/><path class="mia0evx_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:target-01" /></template>
