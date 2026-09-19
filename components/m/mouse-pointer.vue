<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdgookbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1792};
const content = `<path class="kdgookbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mouse-pointer" /></template>
