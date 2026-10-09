<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwy3jw9qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zwy3jw9qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-dim-20-bold" /></template>
