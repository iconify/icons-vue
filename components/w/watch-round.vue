<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld_j4fb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld_j4fb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-round" /></template>
