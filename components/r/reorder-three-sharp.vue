<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxd4l03gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sxd4l03gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:reorder-three-sharp" /></template>
