<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec5jxpckg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ec5jxpckg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:square-caret-up" /></template>
