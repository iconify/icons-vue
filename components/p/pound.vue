<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dubu0bb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="dubu0bb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:pound" /></template>
