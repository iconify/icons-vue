<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdpzmacwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sdpzmacwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:underline" /></template>
