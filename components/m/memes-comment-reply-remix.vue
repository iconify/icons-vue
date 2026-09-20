<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/por2i3b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="por2i3b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:memes-comment-reply-remix" /></template>
