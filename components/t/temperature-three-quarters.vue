<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1goxvk8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="o1goxvk8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-three-quarters" /></template>
