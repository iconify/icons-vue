<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfl834tqx.css';
import '../../css/j/j77zeoa7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gfl834tqx"/><path class="j77zeoa7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-route-20-bold" /></template>
