<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_kl73bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_kl73bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-double-left-round" /></template>
