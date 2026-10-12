<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfu5g5uib.css';
import '../../css/o/o63gs7ffv.css';
import '../../css/n/ne8de7own.css';
import '../../css/h/h8pwwo5-k.css';
import '../../css/o/opyf_kbck.css';
import '../../css/k/ksydp3lsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kfu5g5uib"/><path class="o63gs7ffv"/><path class="ne8de7own"/><path class="h8pwwo5-k"/><path class="opyf_kbck"/><path class="ksydp3lsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pylon-x-48-bold" /></template>
