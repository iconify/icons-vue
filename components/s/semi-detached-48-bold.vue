<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdn7143ls.css';
import '../../css/k/kr6gu5bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tdn7143ls"/><path class="kr6gu5bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:semi-detached-48-bold" /></template>
