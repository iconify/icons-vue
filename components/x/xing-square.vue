<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5ibdneby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="u5ibdneby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:xing-square" /></template>
