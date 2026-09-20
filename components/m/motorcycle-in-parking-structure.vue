<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk0firxwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xk0firxwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-in-parking-structure" /></template>
