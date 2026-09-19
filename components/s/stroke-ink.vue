<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bne9jgbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bne9jgbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stroke-ink" /></template>
