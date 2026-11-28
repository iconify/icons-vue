<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y05fj9bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y05fj9bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:robot-vacuum-clock" /></template>
