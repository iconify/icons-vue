<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-7ml0b5j.css';
import '../../css/z/z1gk-qo7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g-7ml0b5j"/><path class="z1gk-qo7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sofa-20-bold" /></template>
