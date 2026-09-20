<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx3ux99nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yx3ux99nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mounted-slotted-dispenser" /></template>
