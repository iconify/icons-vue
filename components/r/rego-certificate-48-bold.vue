<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj1y5cbbe.css';
import '../../css/u/uh_4a6zja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jj1y5cbbe"/><path class="uh_4a6zja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rego-certificate-48-bold" /></template>
