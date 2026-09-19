<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu_9tcoym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":384};
const content = `<path class="eu_9tcoym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:redo" /></template>
