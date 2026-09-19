<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqkctdb_g.css';
import '../../css/c/cvlo2iq2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eqkctdb_g"/><path class="cvlo2iq2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sim-card" /></template>
