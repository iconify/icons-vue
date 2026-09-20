<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgmx5biec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgmx5biec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:puzzle-fill" /></template>
