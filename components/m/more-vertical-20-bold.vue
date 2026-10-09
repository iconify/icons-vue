<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v58b1ybqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v58b1ybqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:more-vertical-20-bold" /></template>
