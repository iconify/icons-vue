<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir91d7qdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ir91d7qdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shrimp" /></template>
