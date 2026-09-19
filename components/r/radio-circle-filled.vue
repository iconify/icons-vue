<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8w03vp9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8w03vp9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:radio-circle-filled" /></template>
