<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc49c80nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tc49c80nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:underweight-person-standing" /></template>
