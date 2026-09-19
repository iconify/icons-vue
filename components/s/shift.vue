<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbwcy9q0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gbwcy9q0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:shift" /></template>
