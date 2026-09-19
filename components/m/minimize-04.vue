<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lugelcbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lugelcbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:minimize-04" /></template>
