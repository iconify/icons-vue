<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgkmlybqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tgkmlybqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spa-stones-20-bold" /></template>
