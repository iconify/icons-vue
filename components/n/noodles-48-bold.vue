<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke40ke3lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ke40ke3lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:noodles-48-bold" /></template>
