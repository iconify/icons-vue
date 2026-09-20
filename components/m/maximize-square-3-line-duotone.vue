<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yvxo91ekb.css';
import '../../css/h/hb6t3lb4p.css';
import '../../css/r/r9eucsbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yvxo91ekb"/><path class="hb6t3lb4p"/><path class="r9eucsbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-3-line-duotone" /></template>
