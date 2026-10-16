<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqc6deukf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqc6deukf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tsunami-48-bold" /></template>
