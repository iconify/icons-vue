<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpg98ub8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lpg98ub8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:rod-asclepius" /></template>
