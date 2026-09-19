<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2c-q7bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="b2c-q7bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plug" /></template>
