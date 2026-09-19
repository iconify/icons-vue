<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es1mdt2en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="es1mdt2en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sticky" /></template>
