<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv21hpb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv21hpb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:size-warp-filled" /></template>
