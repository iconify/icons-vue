<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0_w1obnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0_w1obnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:unfold-less-bulk-round" /></template>
