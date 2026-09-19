<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohg2owb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ohg2owb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sling2x-outline" /></template>
