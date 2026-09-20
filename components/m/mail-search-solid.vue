<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygh_cx1if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ygh_cx1if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-search-solid" /></template>
