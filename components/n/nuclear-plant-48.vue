<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k16ypzb4q.css';
import '../../css/o/o2az-abuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k16ypzb4q"/><path class="o2az-abuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-48" /></template>
