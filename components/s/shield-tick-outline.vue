<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zcrig_nhd.css';
import '../../css/p/piq9lw_yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="shield-tick-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="zcrig_nhd"/><path class="piq9lw_yy"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:shield-tick-outline" /></template>
