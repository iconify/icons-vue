<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq2xs6b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jq2xs6b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:memes-comment-reply-solid" /></template>
