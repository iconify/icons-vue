<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc1ropbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cc1ropbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:memes-comment-reply-remix" /></template>
