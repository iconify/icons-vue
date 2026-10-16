<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrhhv18_e.css';
import '../../css/x/xo6w-xw4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nrhhv18_e"/><path class="xo6w-xw4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-tester-48-bold" /></template>
