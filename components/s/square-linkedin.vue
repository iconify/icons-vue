<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shqpe6bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="shqpe6bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-linkedin" /></template>
