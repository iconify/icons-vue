<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kthlowbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="kthlowbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:r" /></template>
