<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p54ufnf5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p54ufnf5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-9" /></template>
