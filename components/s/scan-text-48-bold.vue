<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fod-dwb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fod-dwb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-text-48-bold" /></template>
