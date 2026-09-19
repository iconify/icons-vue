<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onoso57ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="onoso57ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:unity" /></template>
