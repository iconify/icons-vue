<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfx2vkxbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfx2vkxbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-dashed" /></template>
