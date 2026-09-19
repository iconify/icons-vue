<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-n1ibyr.css';
import '../../css/z/zfla53asp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8-n1ibyr"/><path class="zfla53asp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-code-download" /></template>
