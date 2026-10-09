<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu_-hqblm.css';
import '../../css/l/lx1bjzy7s.css';
import '../../css/r/rkhp_zb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mu_-hqblm"/><path class="lx1bjzy7s"/><path class="rkhp_zb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:school-48" /></template>
