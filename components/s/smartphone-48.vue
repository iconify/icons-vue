<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6nu2bcpl.css';
import '../../css/t/ts55nda3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6nu2bcpl"/><path class="ts55nda3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-48" /></template>
