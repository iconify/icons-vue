<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_2pd5bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_2pd5bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-2-line" /></template>
