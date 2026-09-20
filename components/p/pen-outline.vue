<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy2a6pbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oy2a6pbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pen-outline" /></template>
