<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u72l21blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="u72l21blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:square-root" /></template>
