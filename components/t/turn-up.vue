<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8adc4r9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q8adc4r9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:turn-up" /></template>
