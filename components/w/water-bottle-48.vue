<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acvp9rbcm.css';
import '../../css/e/ev1t4gbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="acvp9rbcm"/><path class="ev1t4gbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-bottle-48" /></template>
