<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf57_hl-a.css';
import '../../css/q/qrxusubxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cf57_hl-a"/><path class="qrxusubxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:torch-48" /></template>
