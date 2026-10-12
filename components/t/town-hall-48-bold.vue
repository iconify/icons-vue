<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkw_aib9x.css';
import '../../css/o/onixhkbxr.css';
import '../../css/u/umdfmcbpo.css';
import '../../css/a/a00b_rbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkw_aib9x"/><path class="onixhkbxr"/><path class="umdfmcbpo"/><path class="a00b_rbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:town-hall-48-bold" /></template>
