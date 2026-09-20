<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tudg39boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tudg39boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:npm-outline" /></template>
