<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2fhr3bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2fhr3bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-hide-fill" /></template>
