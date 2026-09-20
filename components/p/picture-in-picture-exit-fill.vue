<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4kogebfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4kogebfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:picture-in-picture-exit-fill" /></template>
