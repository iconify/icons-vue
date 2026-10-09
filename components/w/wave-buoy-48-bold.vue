<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhx9-1bok.css';
import '../../css/p/p47yd3vrn.css';
import '../../css/q/qjqywbfqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uhx9-1bok"/><path class="p47yd3vrn"/><path class="qjqywbfqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-buoy-48-bold" /></template>
