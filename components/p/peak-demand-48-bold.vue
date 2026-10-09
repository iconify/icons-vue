<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvxdc7lzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pvxdc7lzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:peak-demand-48-bold" /></template>
