<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/t/ttjl0ecfp.css';
import '../../css/v/vce1w3ven.css';
import '../../css/v/vlsgay-ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="ttjl0ecfp"/><path clip-rule="evenodd" class="vce1w3ven"/><path class="vlsgay-ha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:monitor" /></template>
