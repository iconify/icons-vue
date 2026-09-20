<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7_67ke_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t7_67ke_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:star-full" /></template>
