<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wwxlbdmgr.css';
import '../../css/g/go0njccyz.css';
import '../../css/c/ccm11mbdl.css';
import '../../css/r/rsrhfac5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wwxlbdmgr"/><path class="go0njccyz"/><path class="ccm11mbdl"/><path class="rsrhfac5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-cross-broken" /></template>
