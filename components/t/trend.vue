<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/u/utf5_xbzs.css';
import '../../css/l/ljlrb_qkl.css';
import '../../css/g/g9tzrvvgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="utf5_xbzs"/><path class="ljlrb_qkl"/><path class="g9tzrvvgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:trend" /></template>
