<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-x_d5e7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-x_d5e7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ruler-dimension-line" /></template>
