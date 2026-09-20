<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf2-1wf3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cf2-1wf3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:popcorn-solid" /></template>
