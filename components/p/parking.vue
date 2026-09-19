<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/ghfgsj2ga.css';
import '../../css/k/k16gn-bll.css';
import '../../css/l/llr_2sbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="ghfgsj2ga"/><path class="k16gn-bll"/><path class="llr_2sbko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:parking" /></template>
