<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8h5bgb-m.css';
import '../../css/n/n_xpcc89w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8h5bgb-m"/><path class="n_xpcc89w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nimtable-light" /></template>
