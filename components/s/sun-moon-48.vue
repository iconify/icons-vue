<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_hp02zmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_hp02zmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-moon-48" /></template>
