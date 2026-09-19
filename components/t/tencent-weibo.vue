<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4b3u2b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1216,"height":1792};
const content = `<path class="y4b3u2b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tencent-weibo" /></template>
