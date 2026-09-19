<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4uciobcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4uciobcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:post-solid" /></template>
