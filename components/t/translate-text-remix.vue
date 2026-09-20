<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yct1-hxkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yct1-hxkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:translate-text-remix" /></template>
