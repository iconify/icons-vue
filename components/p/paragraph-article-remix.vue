<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otxob6bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otxob6bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paragraph-article-remix" /></template>
