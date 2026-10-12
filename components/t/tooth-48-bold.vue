<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3yu5jvhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f3yu5jvhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tooth-48-bold" /></template>
