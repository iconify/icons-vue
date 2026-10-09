<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxjqujbwc.css';
import '../../css/l/l1832ablw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fxjqujbwc"/><path class="l1832ablw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiator-48-bold" /></template>
