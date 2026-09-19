<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqa2xhb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqa2xhb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:sound-off-solid" /></template>
