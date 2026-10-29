<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9go7hbsg.css';
import '../../css/v/vaz59h5au.css';
import '../../css/q/q22873scb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9go7hbsg wm-a"/><path class="vaz59h5au wm-k"/><path class="q22873scb wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:pin" /></template>
