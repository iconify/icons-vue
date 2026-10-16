<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rid_tie-o.css';
import '../../css/m/mm9-oj8-f.css';
import '../../css/l/lu5-5ac7f.css';
import '../../css/n/nf6z_ngnm.css';
import '../../css/i/i59g4cbwi.css';
import '../../css/h/hbyn988mt.css';
import '../../css/m/mlgizs1di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rid_tie-o"/><path class="mm9-oj8-f"/><path class="lu5-5ac7f"/><path class="nf6z_ngnm"/><path class="i59g4cbwi"/><path class="hbyn988mt"/><path class="mlgizs1di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:neural-network-48-bold" /></template>
