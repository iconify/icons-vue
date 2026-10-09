<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/end2zdp7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="end2zdp7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-check-48" /></template>
