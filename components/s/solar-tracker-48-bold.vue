<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqs_8pbmm.css';
import '../../css/k/k67ptjbwx.css';
import '../../css/n/nvywobb1g.css';
import '../../css/p/pse5d0bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qqs_8pbmm"/><path class="k67ptjbwx"/><path class="nvywobb1g"/><path class="pse5d0bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tracker-48-bold" /></template>
