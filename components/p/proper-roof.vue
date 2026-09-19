<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9705itxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h9705itxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:proper-roof" /></template>
