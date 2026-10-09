<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv7_53bka.css';
import '../../css/m/m7ftp5n3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mv7_53bka"/><path class="m7ftp5n3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-thermal-48" /></template>
