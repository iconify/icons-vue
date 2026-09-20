<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt11htw0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mt11htw0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:messenger" /></template>
