<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m79bmj2zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m79bmj2zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:up-arrow-1" /></template>
