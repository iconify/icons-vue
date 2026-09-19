<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx2xi1jvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx2xi1jvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:volume-minus" /></template>
