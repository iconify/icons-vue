<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxju_n3um.css';
import '../../css/t/tyo480b-b.css';
import '../../css/o/o-4655baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nxju_n3um"/><path class="tyo480b-b"/><path class="o-4655baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-up-48" /></template>
