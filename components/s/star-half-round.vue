<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un-0dcbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un-0dcbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-half-round" /></template>
