<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obq9c64fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="obq9c64fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:mic-alt" /></template>
