<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb-tgx_gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb-tgx_gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-left-fill-round" /></template>
