<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqzszg6lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qqzszg6lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-descending-above-ground" /></template>
