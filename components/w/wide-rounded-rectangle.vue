<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uul6rcssg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uul6rcssg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-rounded-rectangle" /></template>
