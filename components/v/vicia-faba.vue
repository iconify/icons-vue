<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lxx50rbdy.css';
import '../../css/v/vugmo3b-s.css';
import '../../css/k/ko5q309hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="lxx50rbdy"/><path class="vugmo3b-s"/><path class="ko5q309hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:vicia-faba" /></template>
