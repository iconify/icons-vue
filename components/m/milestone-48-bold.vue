<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv2a2jbrl.css';
import '../../css/x/x41cd7j7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rv2a2jbrl"/><path class="x41cd7j7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:milestone-48-bold" /></template>
