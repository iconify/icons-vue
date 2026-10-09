<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d822ibkfm.css';
import '../../css/p/pmvqjsbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d822ibkfm"/><path class="pmvqjsbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-route-48-bold" /></template>
