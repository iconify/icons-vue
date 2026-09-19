<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtjx3yi_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtjx3yi_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:strikethrough-solid" /></template>
