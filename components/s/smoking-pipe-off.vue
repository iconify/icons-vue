<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_c0p_b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_c0p_b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smoking-pipe-off" /></template>
