<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6yd4ubmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g6yd4ubmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:ruler" /></template>
