<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm8yzh27k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gm8yzh27k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-rocket" /></template>
