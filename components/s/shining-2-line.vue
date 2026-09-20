<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1mnnn-xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1mnnn-xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shining-2-line" /></template>
