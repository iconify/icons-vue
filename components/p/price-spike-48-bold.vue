<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpel3hezc.css';
import '../../css/l/lfuglz5ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="lfuglz5ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-spike-48-bold" /></template>
