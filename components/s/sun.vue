<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehed_lehl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ehed_lehl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:sun" /></template>
