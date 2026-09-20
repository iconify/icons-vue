<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6yp67b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r6yp67b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pen-tool" /></template>
