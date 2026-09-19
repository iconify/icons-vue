<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul4cwdbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ul4cwdbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:polygon" /></template>
