<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iod7dkblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iod7dkblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moonset-48" /></template>
