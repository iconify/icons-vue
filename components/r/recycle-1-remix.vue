<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t042mnbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t042mnbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:recycle-1-remix" /></template>
