<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch3f4qbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ch3f4qbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:product-hunt" /></template>
