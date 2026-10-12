<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_qf0abbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p_qf0abbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:metro-48-bold" /></template>
