<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fef8ywbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fef8ywbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:microscope-outline" /></template>
