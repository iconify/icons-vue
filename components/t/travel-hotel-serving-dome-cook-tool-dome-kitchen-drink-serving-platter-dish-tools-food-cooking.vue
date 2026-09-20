<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeaf2cblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yeaf2cblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-hotel-serving-dome-cook-tool-dome-kitchen-drink-serving-platter-dish-tools-food-cooking" /></template>
