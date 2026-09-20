<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0xmr68qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0xmr68qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-2-linear" /></template>
