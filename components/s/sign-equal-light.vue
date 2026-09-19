<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl93ombwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl93ombwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-equal-light" /></template>
