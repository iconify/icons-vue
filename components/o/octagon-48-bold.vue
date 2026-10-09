<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otpi8ybma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="otpi8ybma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:octagon-48-bold" /></template>
