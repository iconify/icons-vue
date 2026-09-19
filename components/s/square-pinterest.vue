<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvj7x-bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="uvj7x-bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-pinterest" /></template>
