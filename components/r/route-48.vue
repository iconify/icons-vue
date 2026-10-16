<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em_gclcem.css';
import '../../css/n/nfttrft0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="em_gclcem"/><path class="nfttrft0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:route-48" /></template>
