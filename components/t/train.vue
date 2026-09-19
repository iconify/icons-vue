<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3ze4ub9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3ze4ub9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:train" /></template>
