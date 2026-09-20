<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj84vy0fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj84vy0fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tag-free-circle-solid" /></template>
