<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt5z-ac7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt5z-ac7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:move-duotone-round" /></template>
