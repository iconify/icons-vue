<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es8pyblwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="es8pyblwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-minus-48" /></template>
