<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grq6pustu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grq6pustu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pushbase" /></template>
