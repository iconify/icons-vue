<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg45qdbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kg45qdbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:visa" /></template>
