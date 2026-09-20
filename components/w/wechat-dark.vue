<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw8jb2bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lw8jb2bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wechat-dark" /></template>
