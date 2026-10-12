<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfu5g5uib.css';
import '../../css/o/o63gs7ffv.css';
import '../../css/n/ne8de7own.css';
import '../../css/h/h8pwwo5-k.css';
import '../../css/g/gqkml0b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kfu5g5uib"/><path class="o63gs7ffv"/><path class="ne8de7own"/><path class="h8pwwo5-k"/><path class="gqkml0b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pylon-check-48-bold" /></template>
