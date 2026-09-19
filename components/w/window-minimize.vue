<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fstqf0b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fstqf0b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:window-minimize" /></template>
