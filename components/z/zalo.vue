<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2vx3gbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2vx3gbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zalo" /></template>
