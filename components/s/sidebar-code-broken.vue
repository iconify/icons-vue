<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/ml0cb1b5h.css';
import '../../css/w/w434_tbtm.css';
import '../../css/m/mblpvrk8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ml0cb1b5h"/><path class="w434_tbtm"/><path class="mblpvrk8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-code-broken" /></template>
