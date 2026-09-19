<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdfm59b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jdfm59b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-medium" /></template>
