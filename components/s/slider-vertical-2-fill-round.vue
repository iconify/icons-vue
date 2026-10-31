<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1xz1f56j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1xz1f56j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-2-fill-round" /></template>
