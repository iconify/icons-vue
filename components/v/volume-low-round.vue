<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjn55_b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjn55_b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-low-round" /></template>
