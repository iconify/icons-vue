<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga00bibxt.css';
import '../../css/u/u1d_hjplu.css';
import '../../css/o/oiqizvb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ga00bibxt"/><path class="u1d_hjplu"/><path class="oiqizvb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-sock-48" /></template>
