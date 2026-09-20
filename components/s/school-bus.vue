<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb2406bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zb2406bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:school-bus" /></template>
