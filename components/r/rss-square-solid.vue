<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x388a-7-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x388a-7-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rss-square-solid" /></template>
