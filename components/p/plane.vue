<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz8cwkb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lz8cwkb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:plane" /></template>
