<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co-y23bkw.css';
import '../../css/a/aui1l8ddh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="co-y23bkw"/><path class="aui1l8ddh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oven-48" /></template>
