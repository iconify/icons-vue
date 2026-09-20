<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/swsab_86e.css';
import '../../css/f/fw5rt46mg.css';
import '../../css/r/r0yvb3n_z.css';
import '../../css/j/jqt39-bbm.css';
import '../../css/q/q6cbe7bnx.css';
import '../../css/k/kwa31tbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="swsab_86e"/><circle class="fw5rt46mg"/><path class="r0yvb3n_z"/><path class="jqt39-bbm"/><path class="q6cbe7bnx"/><path class="kwa31tbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:usb-broken" /></template>
