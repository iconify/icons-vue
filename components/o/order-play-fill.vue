<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k55i2mb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k55i2mb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:order-play-fill" /></template>
