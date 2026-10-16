<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-flw2bql.css';
import '../../css/v/vbmukxb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-flw2bql"/><path class="vbmukxb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pc-tower-48" /></template>
