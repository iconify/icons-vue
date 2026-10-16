<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc1i690il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oc1i690il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wood-pellets-48-bold" /></template>
