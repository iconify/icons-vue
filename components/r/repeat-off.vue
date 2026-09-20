<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klzqqlbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klzqqlbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:repeat-off" /></template>
