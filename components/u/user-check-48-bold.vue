<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8mx5jbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t8mx5jbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-check-48-bold" /></template>
