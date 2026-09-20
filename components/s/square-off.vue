<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-kp242az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-kp242az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-off" /></template>
