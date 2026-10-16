<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-lmpi58f.css';
import '../../css/y/y3ceaebkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q-lmpi58f"/><path class="y3ceaebkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ups-48-bold" /></template>
