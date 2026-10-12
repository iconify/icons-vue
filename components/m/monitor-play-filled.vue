<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqzx1-bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yqzx1-bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-play-filled" /></template>
