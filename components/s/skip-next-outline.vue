<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8f7b6bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8f7b6bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:skip-next-outline" /></template>
