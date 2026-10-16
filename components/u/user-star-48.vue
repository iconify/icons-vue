<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmfr5cb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dmfr5cb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-star-48" /></template>
