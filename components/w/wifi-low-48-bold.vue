<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xph1b26-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xph1b26-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-low-48-bold" /></template>
