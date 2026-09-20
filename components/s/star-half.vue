<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y72p_ms0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y72p_ms0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:star-half" /></template>
