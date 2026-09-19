<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/w/wi-dq8bor.css';
import '../../css/p/php4bw5yx.css';
import '../../css/t/tq30inb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="wi-dq8bor"/><path class="php4bw5yx"/><path class="tq30inb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:target" /></template>
