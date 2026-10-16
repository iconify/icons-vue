<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw7qwioap.css';
import '../../css/l/l3qc97r_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yw7qwioap"/><path class="l3qc97r_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:network-nodes-48-bold" /></template>
