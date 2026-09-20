<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liv7s6d2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="liv7s6d2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-down-with-plus" /></template>
