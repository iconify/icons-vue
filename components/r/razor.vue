<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lj8xgwb9t.css';
import '../../css/k/kooq7hlhc.css';
import '../../css/e/e814sabwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="lj8xgwb9t"/><path class="kooq7hlhc"/><path class="e814sabwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:razor" /></template>
