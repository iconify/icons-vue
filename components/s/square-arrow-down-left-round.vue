<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbsj4lbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbsj4lbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-left-round" /></template>
