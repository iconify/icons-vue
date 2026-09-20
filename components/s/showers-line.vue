<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efmuaubvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efmuaubvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:showers-line" /></template>
