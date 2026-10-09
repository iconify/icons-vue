<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akt-vlbtw.css';
import '../../css/l/lq07xlbfl.css';
import '../../css/h/hlva2pb_n.css';
import '../../css/e/ex_mzw_ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akt-vlbtw"/><path class="lq07xlbfl"/><path class="hlva2pb_n"/><path class="ex_mzw_ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:portable-solar-48-bold" /></template>
