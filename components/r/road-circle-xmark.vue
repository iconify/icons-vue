<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn4vx2bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jn4vx2bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:road-circle-xmark" /></template>
