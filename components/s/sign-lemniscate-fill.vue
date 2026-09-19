<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ws10x5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7ws10x5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-lemniscate-fill" /></template>
