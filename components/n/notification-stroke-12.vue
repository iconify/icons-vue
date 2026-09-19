<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg3t_8bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cg3t_8bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:notification-stroke-12" /></template>
