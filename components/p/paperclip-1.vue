<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd5brzbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="fd5brzbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paperclip-1" /></template>
