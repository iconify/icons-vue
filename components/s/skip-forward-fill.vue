<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s69z1x1zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s69z1x1zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skip-forward-fill" /></template>
