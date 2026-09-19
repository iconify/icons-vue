<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyeu8actj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pyeu8actj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-plus-20-solid" /></template>
