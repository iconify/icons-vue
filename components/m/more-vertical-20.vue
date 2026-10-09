<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m799961bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m799961bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:more-vertical-20" /></template>
