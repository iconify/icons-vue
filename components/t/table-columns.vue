<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw0wuyiar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uw0wuyiar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:table-columns" /></template>
