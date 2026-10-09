<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd-j1738m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dd-j1738m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:maximize-48" /></template>
