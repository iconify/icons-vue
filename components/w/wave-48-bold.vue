<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjed8tuoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjed8tuoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-48-bold" /></template>
