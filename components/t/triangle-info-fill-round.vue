<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6uw1bcex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6uw1bcex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-info-fill-round" /></template>
