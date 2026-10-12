<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si3nracbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="si3nracbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rows-48" /></template>
