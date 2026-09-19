<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fkpmv0bwm.css';
import '../../css/v/vrcpdj3pt.css';
import '../../css/p/p5xrhsb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fkpmv0bwm"/><path class="vrcpdj3pt"/><path class="p5xrhsb5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-validation-01" /></template>
