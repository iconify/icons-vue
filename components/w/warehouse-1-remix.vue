<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js5um8b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="js5um8b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:warehouse-1-remix" /></template>
