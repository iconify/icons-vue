<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2nxiyvua.css';
import '../../css/g/gs-niz01e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2nxiyvua"/><path class="gs-niz01e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:temperature-48-bold" /></template>
