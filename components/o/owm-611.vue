<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boxar-4qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="boxar-4qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-611" /></template>
