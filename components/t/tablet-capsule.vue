<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp1806bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gp1806bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tablet-capsule" /></template>
