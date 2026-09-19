<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buyk58chx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="buyk58chx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:patient-band-alt" /></template>
