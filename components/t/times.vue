<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl_h1w5_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_h1w5_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:times" /></template>
