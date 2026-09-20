<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jatnfr4_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jatnfr4_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:t-box-fill" /></template>
