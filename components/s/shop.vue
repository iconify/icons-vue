<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed-s9pbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1472};
const content = `<path class="ed-s9pbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:shop" /></template>
