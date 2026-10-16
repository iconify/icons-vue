<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-lmpi58f.css';
import '../../css/f/fw6rn1cfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q-lmpi58f"/><path class="fw6rn1cfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pc-tower-48-bold" /></template>
