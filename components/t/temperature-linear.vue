<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mzuq4x0dn.css';
import '../../css/k/ktz4j74-r.css';
import '../../css/w/w29ath28m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mzuq4x0dn"/><path class="ktz4j74-r"/><path class="w29ath28m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:temperature-linear" /></template>
