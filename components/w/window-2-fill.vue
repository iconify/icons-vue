<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j29p-3uzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j29p-3uzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:window-2-fill" /></template>
