<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfncn9b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<path class="jfncn9b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:stepback" /></template>
