<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7w6f-o8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7w6f-o8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skip-back-48" /></template>
