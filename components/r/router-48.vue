<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5cmpabez.css';
import '../../css/j/jqhtdhbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5cmpabez"/><path class="jqhtdhbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:router-48" /></template>
