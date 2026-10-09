<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uph6w3b8p.css';
import '../../css/q/qo92-j1px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uph6w3b8p"/><path class="qo92-j1px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:newspaper-48-bold" /></template>
