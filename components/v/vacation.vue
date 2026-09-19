<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/ktazicukk.css';
import '../../css/w/wrqafjrbc.css';
import '../../css/b/bmc7y_buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ktazicukk"/><path class="wrqafjrbc"/><path class="bmc7y_buz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:vacation" /></template>
