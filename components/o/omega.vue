<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr4o8ebeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lr4o8ebeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:omega" /></template>
