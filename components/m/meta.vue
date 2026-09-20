<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-8p8db5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="e-8p8db5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:meta" /></template>
