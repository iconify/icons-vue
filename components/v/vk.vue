<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t34a1hbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t34a1hbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:vk" /></template>
