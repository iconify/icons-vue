<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cso4l-5ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cso4l-5ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:malaria-pv-microscope" /></template>
