<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0xf25b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0xf25b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu-09" /></template>
