<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmvltcbxl.css';
import '../../css/f/fhr9nlrmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vmvltcbxl"/><path class="fhr9nlrmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weld-seam-48-bold" /></template>
