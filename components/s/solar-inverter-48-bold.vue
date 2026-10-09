<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnjcr8b9t.css';
import '../../css/z/z6drtmbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnjcr8b9t"/><path class="z6drtmbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-inverter-48-bold" /></template>
