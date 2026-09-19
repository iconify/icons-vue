<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwm4we_ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="uwm4we_ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:shield" /></template>
