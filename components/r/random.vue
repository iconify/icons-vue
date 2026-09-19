<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t38tdl0sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1600};
const content = `<path class="t38tdl0sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:random" /></template>
