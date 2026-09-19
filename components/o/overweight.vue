<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygblixb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ygblixb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:overweight" /></template>
