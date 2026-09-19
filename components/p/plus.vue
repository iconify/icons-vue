<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flyu6zhwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="flyu6zhwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:plus" /></template>
