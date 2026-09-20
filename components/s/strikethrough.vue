<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijxr9ebvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijxr9ebvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:strikethrough" /></template>
