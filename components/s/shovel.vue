<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu0k8jb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu0k8jb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:shovel" /></template>
