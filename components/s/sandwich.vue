<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr3eht-vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cr3eht-vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:sandwich" /></template>
