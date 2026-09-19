<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzz5_vbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lzz5_vbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:retweet" /></template>
