<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-i8x-tan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v-i8x-tan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:snowboard" /></template>
