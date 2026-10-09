<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7sy_0byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v7sy_0byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minimize-48-bold" /></template>
