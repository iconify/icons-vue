<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-flw2bql.css';
import '../../css/x/x-3i40bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-flw2bql"/><path class="x-3i40bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-waste-48" /></template>
