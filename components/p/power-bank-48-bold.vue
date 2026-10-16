<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5qj0td2j.css';
import '../../css/v/vyrx1cnfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h5qj0td2j"/><path class="vyrx1cnfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-bank-48-bold" /></template>
