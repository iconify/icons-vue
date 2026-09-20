<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr32j03ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dr32j03ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-ascending-above-water" /></template>
