<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox9ez0b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ox9ez0b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sun-plant-wilt" /></template>
