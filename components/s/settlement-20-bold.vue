<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptizy_zew.css';
import '../../css/u/u-8r7_bwc.css';
import '../../css/u/usgixfbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ptizy_zew"/><path class="u-8r7_bwc"/><path class="usgixfbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:settlement-20-bold" /></template>
