<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp6su4bex.css';
import '../../css/o/ogcp94bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6su4bex"/><path clip-rule="evenodd" class="ogcp94bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mention-square-bold" /></template>
