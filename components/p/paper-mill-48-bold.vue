<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwjrqmb9j.css';
import '../../css/c/casff0y7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mwjrqmb9j"/><path class="casff0y7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paper-mill-48-bold" /></template>
