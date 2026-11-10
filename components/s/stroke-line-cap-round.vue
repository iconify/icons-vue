<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi814vbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi814vbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stroke-line-cap-round" /></template>
