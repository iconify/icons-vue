<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfla53asp.css';
import '../../css/w/w67qn2bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zfla53asp"/><path class="w67qn2bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-code-working" /></template>
