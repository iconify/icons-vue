<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bir3djc_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bir3djc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:openmrs-logo" /></template>
