<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzu3_9bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hzu3_9bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:truck-medical" /></template>
