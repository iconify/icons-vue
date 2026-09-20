<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j34rt5j7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j34rt5j7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:t-shirt-v" /></template>
