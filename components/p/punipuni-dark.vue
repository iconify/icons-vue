<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy-x3bcet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy-x3bcet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:punipuni-dark" /></template>
