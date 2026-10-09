<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy12kb2lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cy12kb2lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:menu-48-bold" /></template>
