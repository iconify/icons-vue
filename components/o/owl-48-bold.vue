<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugd2fac-m.css';
import '../../css/x/x5g82_bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ugd2fac-m"/><path class="x5g82_bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:owl-48-bold" /></template>
