<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcmmanq0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lcmmanq0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sleigh" /></template>
