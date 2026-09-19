<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/o8be8xbcw.css';
import '../../css/t/tnr_zqylo.css';
import '../../css/h/hghintd6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="o8be8xbcw"/><path class="tnr_zqylo"/><path class="hghintd6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:search" /></template>
