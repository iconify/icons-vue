<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f82vk1b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f82vk1b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:metro" /></template>
