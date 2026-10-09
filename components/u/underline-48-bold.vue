<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7054tbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7054tbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underline-48-bold" /></template>
