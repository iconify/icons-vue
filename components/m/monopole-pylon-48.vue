<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-l0jd7mu.css';
import '../../css/r/rt3djzbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-l0jd7mu"/><path class="rt3djzbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopole-pylon-48" /></template>
