<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnjw03tfc.css';
import '../../css/n/nmjmojkvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nnjw03tfc"/><path class="nmjmojkvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:silicon-48-bold" /></template>
