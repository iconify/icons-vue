<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vrf_umb-v.css';
import '../../css/j/jpoivdq2g.css';
import '../../css/d/dz-1iivjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vrf_umb-v"/><path class="jpoivdq2g"/><path class="dz-1iivjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:navigation-sketch" /></template>
