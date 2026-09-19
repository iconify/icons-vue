<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8mty44yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="l8mty44yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:ok" /></template>
