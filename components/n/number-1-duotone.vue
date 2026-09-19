<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj61mt9fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj61mt9fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-1-duotone" /></template>
