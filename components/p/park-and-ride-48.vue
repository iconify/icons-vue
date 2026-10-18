<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtl8kcc2s.css';
import '../../css/a/a03juec7r.css';
import '../../css/c/cnx91p7lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mtl8kcc2s"/><path class="a03juec7r"/><path class="cnx91p7lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:park-and-ride-48" /></template>
