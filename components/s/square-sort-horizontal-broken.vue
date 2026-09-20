<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c_dm05blc.css';
import '../../css/a/aq5i5kwsa.css';
import '../../css/s/si_mtzbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_dm05blc"/><path class="aq5i5kwsa"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-sort-horizontal-broken" /></template>
