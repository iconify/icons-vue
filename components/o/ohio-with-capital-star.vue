<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyk45popi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nyk45popi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ohio-with-capital-star" /></template>
