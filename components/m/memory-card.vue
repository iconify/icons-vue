<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi97gm6_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi97gm6_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:memory-card" /></template>
