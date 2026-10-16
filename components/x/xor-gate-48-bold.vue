<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kllrszb1h.css';
import '../../css/q/q6laauggs.css';
import '../../css/d/d3uhlcbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kllrszb1h"/><path class="q6laauggs"/><path class="d3uhlcbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:xor-gate-48-bold" /></template>
