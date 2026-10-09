<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn6as_b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qn6as_b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skip-back-48-bold" /></template>
