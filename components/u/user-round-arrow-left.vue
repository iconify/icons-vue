<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0qigtbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0qigtbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-arrow-left" /></template>
