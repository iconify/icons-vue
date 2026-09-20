<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/n/nz26t1bjz.css';
import '../../css/b/bb9pv_wal.css';
import '../../css/h/h_tsn8bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="nz26t1bjz"/><path class="bb9pv_wal"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:money" /></template>
