<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvzp7_oqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rvzp7_oqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:paved-road-alt" /></template>
