<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbyvcib6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tbyvcib6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user" /></template>
