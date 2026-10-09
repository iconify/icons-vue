<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayli8kbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ayli8kbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:welding-48" /></template>
