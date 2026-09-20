<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8mufgdiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l8mufgdiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:washington-with-capital-star" /></template>
