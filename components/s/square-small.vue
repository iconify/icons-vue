<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nujxrcbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nujxrcbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:square-small" /></template>
