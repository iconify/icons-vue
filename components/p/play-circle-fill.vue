<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzwzsybgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzwzsybgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-circle-fill" /></template>
