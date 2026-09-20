<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5vkzebrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5vkzebrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pickax-fill" /></template>
