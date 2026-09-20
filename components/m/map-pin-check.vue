<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/qpejv9b5c.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/u/ulq2j1bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qpejv9b5c"/><circle class="zv6cqnbnp"/><path class="ulq2j1bcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-check" /></template>
