<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7474gbcq.css';
import '../../css/f/fk4kw9brn.css';
import '../../css/k/knmmfib1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w7474gbcq"/><path class="fk4kw9brn"/><path class="knmmfib1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stopwatch-48" /></template>
