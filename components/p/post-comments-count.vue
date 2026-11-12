<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo76gwbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo76gwbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-comments-count" /></template>
