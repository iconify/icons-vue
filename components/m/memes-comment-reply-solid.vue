<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro8o2ub6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro8o2ub6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:memes-comment-reply-solid" /></template>
