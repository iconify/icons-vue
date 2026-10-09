<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sok4o7bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sok4o7bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shapes-48-bold" /></template>
