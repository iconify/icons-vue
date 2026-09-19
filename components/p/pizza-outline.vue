<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycsa12osl.css';
import '../../css/n/n3hic-b0a.css';
import '../../css/u/u7oebpbpx.css';
import '../../css/s/sxc6tccln.css';
import '../../css/e/egjqshbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ycsa12osl"/><path class="n3hic-b0a"/><circle class="u7oebpbpx"/><circle class="sxc6tccln"/><circle class="egjqshbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pizza-outline" /></template>
