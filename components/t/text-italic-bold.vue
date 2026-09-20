<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zep153b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zep153b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-bold" /></template>
