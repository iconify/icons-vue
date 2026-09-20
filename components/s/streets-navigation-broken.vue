<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u7mrcgb5f.css';
import '../../css/p/pqodc7b_d.css';
import '../../css/i/issl78bgr.css';
import '../../css/s/sp_jcmb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u7mrcgb5f"/><path class="pqodc7b_d"/><path class="issl78bgr"/><path class="sp_jcmb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-navigation-broken" /></template>
