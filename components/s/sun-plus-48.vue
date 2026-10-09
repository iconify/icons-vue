<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrpvxrlxf.css';
import '../../css/v/v-3r9t8cb.css';
import '../../css/c/cal94qbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vrpvxrlxf"/><path class="v-3r9t8cb"/><path class="cal94qbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-plus-48" /></template>
