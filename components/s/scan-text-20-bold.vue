<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1wonjgnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s1wonjgnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-text-20-bold" /></template>
