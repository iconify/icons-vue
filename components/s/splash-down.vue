<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtucq6bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mtucq6bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:splash-down" /></template>
