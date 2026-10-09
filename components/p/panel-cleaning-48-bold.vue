<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0k-gcok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ln0k-gcok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-cleaning-48-bold" /></template>
