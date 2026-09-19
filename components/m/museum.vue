<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfc33kbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hfc33kbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:museum" /></template>
