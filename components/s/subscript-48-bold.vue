<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd9ctrbds.css';
import '../../css/h/h-zg-r21y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dd9ctrbds"/><path class="h-zg-r21y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subscript-48-bold" /></template>
