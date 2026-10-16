<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jocyyo5fc.css';
import '../../css/n/nhe1boyvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jocyyo5fc"/><path class="nhe1boyvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nozzle-48-bold" /></template>
