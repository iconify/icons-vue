<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa397kb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa397kb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:router-line" /></template>
