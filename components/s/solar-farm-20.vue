<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc_igi0bl.css';
import '../../css/w/wk2rzac0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nc_igi0bl"/><path class="wk2rzac0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-20" /></template>
