<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb0jupbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bb0jupbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-moon-48-bold" /></template>
