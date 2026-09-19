<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_-8nybyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_-8nybyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shrink-left-filled" /></template>
