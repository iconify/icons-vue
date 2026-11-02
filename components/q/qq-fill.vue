<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf1xo9n8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf1xo9n8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qq-fill" /></template>
