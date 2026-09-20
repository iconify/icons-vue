<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqvjw5zyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqvjw5zyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:restaurant-2-fill" /></template>
