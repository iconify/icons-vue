<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooqpa4igp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ooqpa4igp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-rose-48" /></template>
