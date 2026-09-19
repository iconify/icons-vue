<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv32racfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv32racfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:volume" /></template>
