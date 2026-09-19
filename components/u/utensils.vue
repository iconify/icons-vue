<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs0stz29d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="cs0stz29d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:utensils" /></template>
