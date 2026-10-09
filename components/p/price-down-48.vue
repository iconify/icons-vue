<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ftczb6h.css';
import '../../css/d/dlrxuzy1s.css';
import '../../css/k/kyrmlcowv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g1ftczb6h"/><path class="dlrxuzy1s"/><path class="kyrmlcowv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-down-48" /></template>
