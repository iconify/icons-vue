<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yma2139fj.css';
import '../../css/w/w434_tbtm.css';
import '../../css/m/ml0cb1b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yma2139fj"/><path class="w434_tbtm"/><path class="ml0cb1b5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-right-open-broken" /></template>
