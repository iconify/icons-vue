<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mexbaph4c.css';
import '../../css/c/c89fhw9bu.css';
import '../../css/l/lm4-qnbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mexbaph4c"/><path class="c89fhw9bu"/><path class="lm4-qnbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:micro-hydro-48" /></template>
