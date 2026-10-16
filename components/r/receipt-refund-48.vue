<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oegrs6bql.css';
import '../../css/s/sdign8ysz.css';
import '../../css/k/kl3wgccdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oegrs6bql"/><path class="sdign8ysz"/><path class="kl3wgccdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:receipt-refund-48" /></template>
