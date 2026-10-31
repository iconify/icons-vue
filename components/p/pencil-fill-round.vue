<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjd-bfbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjd-bfbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-fill-round" /></template>
