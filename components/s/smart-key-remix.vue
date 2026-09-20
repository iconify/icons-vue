<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzjc2bc_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fzjc2bc_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:smart-key-remix" /></template>
