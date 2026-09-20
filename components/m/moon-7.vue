<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic8wy5bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ic8wy5bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-7" /></template>
