<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2d_w6b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="z2d_w6b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:quote-right" /></template>
