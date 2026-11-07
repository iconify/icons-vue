<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cw80_bb7p.css';
import '../../css/m/mjj4-z-4p.css';
import '../../css/h/hxmvn4bez.css';
import '../../css/m/mi1n120me.css';
import '../../css/k/km54nzbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cw80_bb7p"/><path class="mjj4-z-4p"/><path class="hxmvn4bez"/><path class="mi1n120me"/><path class="km54nzbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tv-line-duotone" /></template>
