<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e98m9bc_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e98m9bc_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sticky-note" /></template>
