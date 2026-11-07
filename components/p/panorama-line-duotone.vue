<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/ft-nr84oc.css';
import '../../css/z/zia4plbis.css';
import '../../css/x/xbt_tmtte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ft-nr84oc"/><path class="zia4plbis"/><path class="xbt_tmtte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panorama-line-duotone" /></template>
