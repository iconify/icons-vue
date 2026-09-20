<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff1u0l6vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ff1u0l6vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mouse-pointer" /></template>
