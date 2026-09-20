<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly1ve4w5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly1ve4w5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:x-square-filled" /></template>
