<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5plleb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5plleb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rectangle-vertical" /></template>
