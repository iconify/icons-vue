<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdyvsub5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jdyvsub5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tooth-negative" /></template>
