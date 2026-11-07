<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn68y7huu.css';
import '../../css/h/hwymrt-6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn68y7huu"/><path class="hwymrt-6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:podcast-bold" /></template>
