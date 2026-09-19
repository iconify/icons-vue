<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja0jd1bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="ja0jd1bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:website" /></template>
