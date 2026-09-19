<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivczqoblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ivczqoblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:malaria-mixed-microscope2x-outline" /></template>
