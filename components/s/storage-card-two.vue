<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/l/l3kdmty5i.css';
import '../../css/d/d8omfabsq.css';
import '../../css/t/tq9o39b5i.css';
import '../../css/u/uictozznf.css';
import '../../css/q/q3f6kmbgw.css';
import '../../css/c/c2e_75s_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="l3kdmty5i"/><path class="d8omfabsq"/><rect class="tq9o39b5i"/><path class="uictozznf"/><path class="q3f6kmbgw"/><path class="c2e_75s_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:storage-card-two" /></template>
