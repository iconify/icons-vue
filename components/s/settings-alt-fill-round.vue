<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqahxcbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqahxcbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-alt-fill-round" /></template>
