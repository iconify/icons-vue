<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npwtzq6gi.css';
import '../../css/u/uq5sy7bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="npwtzq6gi"/><path class="uq5sy7bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oven-20-bold" /></template>
