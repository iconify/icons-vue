<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik1b_sbhm.css';
import '../../css/e/ecaknubvs.css';
import '../../css/o/o094g_j_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ik1b_sbhm"/><path class="ecaknubvs"/><path class="o094g_j_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-platform-48" /></template>
