<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9-rrjd5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="z9-rrjd5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:square-caret-left" /></template>
