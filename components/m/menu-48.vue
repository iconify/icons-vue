<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeyn_tb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qeyn_tb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:menu-48" /></template>
