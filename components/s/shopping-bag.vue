<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhrifkb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rhrifkb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-bag" /></template>
