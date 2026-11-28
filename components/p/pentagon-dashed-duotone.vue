<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osmynbc3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osmynbc3o primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pentagon-dashed-duotone" /></template>
